<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo8v5jbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bo8v5jbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-pdf-fill-12" {...props}></Icon>
