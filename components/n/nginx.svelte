<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilvw46oto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilvw46oto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nginx" {...props}></Icon>
