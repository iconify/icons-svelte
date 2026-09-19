<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9qcqtbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a9qcqtbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:gumroad" {...props}></Icon>
