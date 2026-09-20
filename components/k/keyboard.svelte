<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb-pztdcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nb-pztdcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:keyboard" {...props}></Icon>
