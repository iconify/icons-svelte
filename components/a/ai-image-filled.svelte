<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcc7li89s.css';
import '../../css/w/w97i0hbdf.css';
import '../../css/j/j9emnib3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcc7li89s"/><path class="w97i0hbdf"/><path class="j9emnib3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-image-filled" {...props}></Icon>
