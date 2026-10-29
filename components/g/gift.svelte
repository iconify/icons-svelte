<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqb102bra.css';
import '../../css/f/fcae2s9ga.css';
import '../../css/h/hw2roquec.css';
import '../../css/m/mch358e_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a wqb102bra"/><path class="fcae2s9ga wm-k"/><path class="hw2roquec wm-k"/><path class="mch358e_u wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:gift" {...props}></Icon>
