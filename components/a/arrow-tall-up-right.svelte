<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxv9obbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lxv9obbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:arrow-tall-up-right" {...props}></Icon>
