<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xck5rbc3z.css';
import '../../css/x/xvz10obcq.css';
import '../../css/e/e24252bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path class="xvz10obcq"/><path class="e24252bcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:email-attachment-document" {...props}></Icon>
