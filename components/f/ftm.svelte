<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6pwpnejz.css';
import '../../css/w/wgjjxmigs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6pwpnejz"/><path class="wgjjxmigs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ftm" {...props}></Icon>
