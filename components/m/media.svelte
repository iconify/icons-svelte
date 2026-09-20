<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onfg9s0lo.css';
import '../../css/l/l1tk6nbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onfg9s0lo"/><path class="l1tk6nbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:media" {...props}></Icon>
