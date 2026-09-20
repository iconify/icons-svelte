<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnf772bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fnf772bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:phone-actions-bluetooth" {...props}></Icon>
