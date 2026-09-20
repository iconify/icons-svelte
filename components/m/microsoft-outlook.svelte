<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1gyudb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1gyudb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-outlook" {...props}></Icon>
