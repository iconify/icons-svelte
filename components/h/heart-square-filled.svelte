<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhjb5xbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhjb5xbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:heart-square-filled" {...props}></Icon>
