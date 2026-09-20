<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl39icczy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl39icczy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:health-potion-outline" {...props}></Icon>
