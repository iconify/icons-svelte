<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko66yhb_i.css';
import '../../css/u/uvq16eblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko66yhb_i"/><path class="uvq16eblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image-sparkle" {...props}></Icon>
