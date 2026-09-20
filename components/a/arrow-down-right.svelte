<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odyw2fb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="odyw2fb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:arrow-down-right" {...props}></Icon>
