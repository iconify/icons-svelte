<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8smtgk6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="i8smtgk6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:interpreter-services" {...props}></Icon>
