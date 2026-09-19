<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv8njj-dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tv8njj-dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mail-pause" {...props}></Icon>
