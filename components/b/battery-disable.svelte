<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/her-4ob5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="her-4ob5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-disable" {...props}></Icon>
