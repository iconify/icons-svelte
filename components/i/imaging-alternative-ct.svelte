<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i79vyfvhr.css';
import '../../css/y/yuh6-fbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="i79vyfvhr"/><path class="yuh6-fbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:imaging-alternative-ct" {...props}></Icon>
