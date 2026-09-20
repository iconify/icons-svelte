<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxdpo6ipa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zxdpo6ipa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:backspace-filled" {...props}></Icon>
