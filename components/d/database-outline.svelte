<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og0ik0mwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og0ik0mwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-outline" {...props}></Icon>
