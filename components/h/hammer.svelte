<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woqf0obxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="woqf0obxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:hammer" {...props}></Icon>
