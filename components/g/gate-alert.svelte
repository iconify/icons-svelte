<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mld5sg2zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mld5sg2zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gate-alert" {...props}></Icon>
