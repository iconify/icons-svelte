<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utqzt6bcp.css';
import '../../css/g/g1pjbqb5c.css';
import '../../css/q/qrntc0b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utqzt6bcp wm-k"/><path class="g1pjbqb5c wm-a"/><path class="qrntc0b5o wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:laugh" {...props}></Icon>
