<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj-m25pot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj-m25pot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lotion-plus" {...props}></Icon>
