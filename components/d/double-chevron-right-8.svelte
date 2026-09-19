<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3eoygbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="k3eoygbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:double-chevron-right-8" {...props}></Icon>
