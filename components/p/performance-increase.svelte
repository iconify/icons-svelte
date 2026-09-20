<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngrep6yjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngrep6yjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:performance-increase" {...props}></Icon>
