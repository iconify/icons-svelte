<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h192o0bpw.css';
import '../../css/h/h_9pgub4l.css';
import '../../css/b/bui30ldye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h192o0bpw"/><path class="h_9pgub4l"/><path class="bui30ldye"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:pointers-fill" {...props}></Icon>
