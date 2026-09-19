<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xby4ho1hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xby4ho1hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-rotate-right-number-5" {...props}></Icon>
