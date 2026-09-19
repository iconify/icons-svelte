<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqxzfac2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqxzfac2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bookmark-filled" {...props}></Icon>
