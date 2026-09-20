<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktpt-8bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ktpt-8bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:paper-clock-light" {...props}></Icon>
