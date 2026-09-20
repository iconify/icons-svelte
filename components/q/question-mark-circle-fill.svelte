<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5s7e3c_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5s7e3c_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:question-mark-circle-fill" {...props}></Icon>
