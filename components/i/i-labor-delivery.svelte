<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgmwywfnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hgmwywfnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-labor-delivery" {...props}></Icon>
