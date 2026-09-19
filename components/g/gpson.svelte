<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6rc42bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z6rc42bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:gpson" {...props}></Icon>
