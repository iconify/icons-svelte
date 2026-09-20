<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv1wf3b6f.css';
import '../../css/g/gwcvmlj-e.css';
import '../../css/q/q_y0g-4dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv1wf3b6f"/><path class="gwcvmlj-e"/><path class="q_y0g-4dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:inbox-upload-fill" {...props}></Icon>
