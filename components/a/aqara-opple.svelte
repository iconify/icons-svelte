<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq4b9qbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq4b9qbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-opple" {...props}></Icon>
