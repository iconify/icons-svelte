<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7wjvtb8g.css';
import '../../css/r/ra875cffg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7wjvtb8g"/><path class="ra875cffg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-3d-question-mark-fill" {...props}></Icon>
