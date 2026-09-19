<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p15-u2b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p15-u2b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:keycdn" {...props}></Icon>
