<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs38c2b8t.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rd0bcganj.css';
import '../../css/m/m5o785bkx.css';
import '../../css/l/liigi-hmf.css';
import '../../css/t/t66ofv8qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs38c2b8t secondary"/><g class="dt0cm9dhy primary"><path class="rd0bcganj"/><path class="m5o785bkx"/><path class="liigi-hmf"/><path class="t66ofv8qu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dice-d4-duo" {...props}></Icon>
