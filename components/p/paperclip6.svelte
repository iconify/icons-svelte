<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qter91nah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qter91nah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paperclip6" {...props}></Icon>
