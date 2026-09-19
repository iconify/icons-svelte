<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suvk3db8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="suvk3db8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:info-filled" {...props}></Icon>
