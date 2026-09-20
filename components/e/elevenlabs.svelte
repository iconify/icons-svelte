<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq-gu0buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq-gu0buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:elevenlabs" {...props}></Icon>
