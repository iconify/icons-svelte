<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-06mp7dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-06mp7dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:last-fm-alt" {...props}></Icon>
