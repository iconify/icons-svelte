<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyiq52k8l.css';
import '../../css/m/m1abqtscw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hyiq52k8l"/><path class="m1abqtscw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:mashroom" {...props}></Icon>
