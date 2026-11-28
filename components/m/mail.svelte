<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5i9iz6bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5i9iz6bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mail" {...props}></Icon>
