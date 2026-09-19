<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw789qb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw789qb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:abarth" {...props}></Icon>
