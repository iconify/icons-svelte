<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vyc35wp7q.css';
import '../../css/p/pappmcc6h.css';
import '../../css/u/uylg6bcvj.css';
import '../../css/b/bamhgjb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vyc35wp7q"/><path class="pappmcc6h wm-a"/><path class="uylg6bcvj"/><path class="bamhgjb2p wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:notepad-text-duo" {...props}></Icon>
