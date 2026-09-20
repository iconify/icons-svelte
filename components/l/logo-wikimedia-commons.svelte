<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyroutbbi.css';
import '../../css/d/dgmtc731l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vyroutbbi"/><circle class="dgmtc731l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-wikimedia-commons" {...props}></Icon>
