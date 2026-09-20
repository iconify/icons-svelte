<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlu19nbng.css';
import '../../css/h/hs0kickzo.css';
import '../../css/o/o-6k8fv8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlu19nbng"/><path class="hs0kickzo"/><path class="o-6k8fv8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:gesture-double-tap-bold" {...props}></Icon>
