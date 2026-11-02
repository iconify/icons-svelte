<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmke3m5bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmke3m5bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:profile-line" {...props}></Icon>
