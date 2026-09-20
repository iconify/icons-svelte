<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f--jrem6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f--jrem6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:color-picker-2-bold" {...props}></Icon>
