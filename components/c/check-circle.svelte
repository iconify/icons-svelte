<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpn46pbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpn46pbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:check-circle" {...props}></Icon>
