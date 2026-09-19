<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxtlc09iq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxtlc09iq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:question-mark" {...props}></Icon>
