<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/icebpjgqg.css';
import '../../css/k/k9yaaohqa.css';
import '../../css/z/znt-8tb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="icebpjgqg"/><path class="k9yaaohqa wm-s"/><path class="znt-8tb8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:phone-off-duo" {...props}></Icon>
