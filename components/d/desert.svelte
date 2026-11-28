<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi_p0qsvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi_p0qsvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:desert" {...props}></Icon>
