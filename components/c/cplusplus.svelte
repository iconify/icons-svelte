<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glo50x2fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="glo50x2fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cplusplus" {...props}></Icon>
