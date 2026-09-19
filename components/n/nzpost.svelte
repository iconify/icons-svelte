<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcd9tq4hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcd9tq4hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nzpost" {...props}></Icon>
