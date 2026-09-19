<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql09f5usd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ql09f5usd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-sm-stroke-12" {...props}></Icon>
