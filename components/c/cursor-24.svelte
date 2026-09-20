<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwaufjzwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwaufjzwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:cursor-24" {...props}></Icon>
