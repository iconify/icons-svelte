<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woxwkpz4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woxwkpz4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:not-superset-filled" {...props}></Icon>
