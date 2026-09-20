<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ppgbcvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ppgbcvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:image-v" {...props}></Icon>
