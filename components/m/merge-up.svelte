<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd1m31bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd1m31bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:merge-up" {...props}></Icon>
