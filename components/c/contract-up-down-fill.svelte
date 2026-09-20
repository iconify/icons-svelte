<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw2irthau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw2irthau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contract-up-down-fill" {...props}></Icon>
