<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx14ww5ye.css';
import '../../css/v/vje-gkoqo.css';
import '../../css/h/hrdjp705l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx14ww5ye wm-k"/><path class="vje-gkoqo wm-a"/><path class="hrdjp705l wm-deco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:rotate-ccw" {...props}></Icon>
