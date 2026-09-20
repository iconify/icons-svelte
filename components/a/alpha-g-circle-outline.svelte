<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/git3lrbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="git3lrbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-g-circle-outline" {...props}></Icon>
