<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2m9b2bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2m9b2bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-3-circle-outline" {...props}></Icon>
