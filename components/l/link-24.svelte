<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rde87_mjj.css';
import '../../css/g/g9uw349nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rde87_mjj"/><path class="g9uw349nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:link-24" {...props}></Icon>
