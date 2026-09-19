<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/yuyn37ibu.css';
import '../../css/m/m9nrudbxy.css';
import '../../css/v/vfwh6zbcp.css';
import '../../css/t/tl9wkhqgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="yuyn37ibu"/><circle class="m9nrudbxy"/><path class="vfwh6zbcp"/><path class="tl9wkhqgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:camper" {...props}></Icon>
