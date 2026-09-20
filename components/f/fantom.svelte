<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqs_ijbso.css';
import '../../css/g/g1vnq256e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xqs_ijbso"/><path class="g1vnq256e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fantom" {...props}></Icon>
