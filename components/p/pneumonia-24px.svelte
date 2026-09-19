<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxa5l4b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wxa5l4b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pneumonia-24px" {...props}></Icon>
