<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjmdt3wxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjmdt3wxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:icon-filled" {...props}></Icon>
