<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpd8tnbks.css';
import '../../css/y/yzp5midtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpd8tnbks"/><path class="yzp5midtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:comment-quote" {...props}></Icon>
