<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knyvgjvpz.css';
import '../../css/f/fbz-pkkzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knyvgjvpz"/><path class="fbz-pkkzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:automation-filled" {...props}></Icon>
