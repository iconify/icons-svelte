<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrtryqu9x.css';
import '../../css/k/ke7qhdp9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrtryqu9x"/><path class="ke7qhdp9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:microphone-alt" {...props}></Icon>
