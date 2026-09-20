<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wu23-3bwn.css';
import '../../css/o/obkdnvb0e.css';
import '../../css/q/qh4l7r3-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wu23-3bwn"/><circle class="obkdnvb0e"/><circle class="qh4l7r3-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:question-circle" {...props}></Icon>
