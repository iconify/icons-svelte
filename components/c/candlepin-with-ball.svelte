<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upuqfew_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="upuqfew_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:candlepin-with-ball" {...props}></Icon>
