<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1ovajluh.css';
import '../../css/u/u4bxzabim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1ovajluh"/><path class="u4bxzabim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:desktop-computer-1-bold" {...props}></Icon>
