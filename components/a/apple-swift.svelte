<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5ktppllt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5ktppllt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:apple-swift" {...props}></Icon>
