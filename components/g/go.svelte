<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_53u5p7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k_53u5p7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:go" {...props}></Icon>
