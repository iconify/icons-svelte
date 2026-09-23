<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe-xkcbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe-xkcbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hash-fill" {...props}></Icon>
