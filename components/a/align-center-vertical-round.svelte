<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wajmslbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wajmslbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-center-vertical-round" {...props}></Icon>
