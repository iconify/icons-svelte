<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axg1wdx3v.css';
import '../../css/n/n5p315boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axg1wdx3v"/><path class="n5p315boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-phone-outgoing" {...props}></Icon>
