<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxko29b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxko29b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-classic-hung-3" {...props}></Icon>
