<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwi52woow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwi52woow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:keyboard-option-bold" {...props}></Icon>
