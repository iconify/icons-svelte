<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxzp69sea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxzp69sea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:performance-money-decrease-bold" {...props}></Icon>
