<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqle3ab3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqle3ab3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-return" {...props}></Icon>
