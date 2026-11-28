<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu-2u4b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu-2u4b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dice-5" {...props}></Icon>
