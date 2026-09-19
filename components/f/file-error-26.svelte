<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2atjnb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":26};
const content = `<path class="y2atjnb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-error-26" {...props}></Icon>
