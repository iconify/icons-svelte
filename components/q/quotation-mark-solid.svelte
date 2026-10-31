<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv21jdfsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hv21jdfsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:quotation-mark-solid" {...props}></Icon>
