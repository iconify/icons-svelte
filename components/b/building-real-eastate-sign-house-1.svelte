<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knlfp1bfs.css';
import '../../css/n/ngqnexboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="knlfp1bfs"/><path class="ngqnexboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:building-real-eastate-sign-house-1" {...props}></Icon>
