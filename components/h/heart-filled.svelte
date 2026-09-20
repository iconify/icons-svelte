<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv1e5xb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wv1e5xb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:heart-filled" {...props}></Icon>
