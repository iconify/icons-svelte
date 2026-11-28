<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-_0m3bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-_0m3bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:briefcase" {...props}></Icon>
