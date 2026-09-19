<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me96k3bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="me96k3bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:college-football" {...props}></Icon>
