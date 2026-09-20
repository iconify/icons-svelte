<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsriy4b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsriy4b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:browser-24" {...props}></Icon>
