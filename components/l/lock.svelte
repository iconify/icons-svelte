<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urfzs4bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="urfzs4bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:lock" {...props}></Icon>
