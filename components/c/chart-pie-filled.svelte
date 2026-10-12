<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moc096_4x.css';
import '../../css/h/ha-x6codx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moc096_4x"/><path class="ha-x6codx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chart-pie-filled" {...props}></Icon>
