<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe5ywzbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe5ywzbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-off" {...props}></Icon>
