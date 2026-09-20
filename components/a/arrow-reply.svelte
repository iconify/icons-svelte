<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr4b4bdaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr4b4bdaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-reply" {...props}></Icon>
