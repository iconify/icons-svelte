<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbv_7acjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbv_7acjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up-3" {...props}></Icon>
