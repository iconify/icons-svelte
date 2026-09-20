<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5b2csbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5b2csbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:light-mode-bright-dark-bold" {...props}></Icon>
