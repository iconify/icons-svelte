<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emurcabap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emurcabap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gift-filled" {...props}></Icon>
