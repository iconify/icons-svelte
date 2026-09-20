<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckgm-9y5r.css';
import '../../css/v/v_xa8ibqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ckgm-9y5r"/><path class="v_xa8ibqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:programming-code-idea" {...props}></Icon>
