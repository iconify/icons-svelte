<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwwq52lah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwwq52lah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-lamp-plafond" {...props}></Icon>
