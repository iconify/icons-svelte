<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7uwmjy0t.css';
import '../../css/m/mg-6g4b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7uwmjy0t"/><path class="mg-6g4b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:inbox-star-fill" {...props}></Icon>
