<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjpr6kb9a.css';
import '../../css/m/mlayuqb-h.css';
import '../../css/d/dpf700fwr.css';
import '../../css/q/qmp0aacci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="xjpr6kb9a"/><path class="mlayuqb-h"/><path class="dpf700fwr"/><path class="qmp0aacci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:japanese-service-charge-button" {...props}></Icon>
