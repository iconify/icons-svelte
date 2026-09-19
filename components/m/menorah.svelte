<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjf14cbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjf14cbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:menorah" {...props}></Icon>
