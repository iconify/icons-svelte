<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enisynbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="enisynbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-db2-alt" {...props}></Icon>
