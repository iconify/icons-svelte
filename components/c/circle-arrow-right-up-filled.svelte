<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb-s_fb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eb-s_fb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrow-right-up-filled" {...props}></Icon>
