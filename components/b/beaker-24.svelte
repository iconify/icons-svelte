<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4mbnrhsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4mbnrhsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:beaker-24" {...props}></Icon>
