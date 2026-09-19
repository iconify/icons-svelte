<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkp_bd6ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkp_bd6ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-curtain" {...props}></Icon>
