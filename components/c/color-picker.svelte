<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxc5c4b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxc5c4b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:color-picker" {...props}></Icon>
