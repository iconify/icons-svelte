<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpl9-m38e.css';
import '../../css/w/wrto5cmdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kpl9-m38e"/><path class="wrto5cmdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:error-filled" {...props}></Icon>
