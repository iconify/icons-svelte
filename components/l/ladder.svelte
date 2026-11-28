<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thh976iif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thh976iif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ladder" {...props}></Icon>
