<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvkw6gb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kvkw6gb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-plus" {...props}></Icon>
