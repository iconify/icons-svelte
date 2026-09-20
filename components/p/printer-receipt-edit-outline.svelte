<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p799onbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p799onbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-receipt-edit-outline" {...props}></Icon>
