<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4okflb5a.css';
import '../../css/j/jardiabnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4okflb5a secondary"/><path class="jardiabnv primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cross-duo" {...props}></Icon>
