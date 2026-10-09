<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0d-k9bod.css';
import '../../css/i/iuszqrjvz.css';
import '../../css/q/qz4brhaoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w0d-k9bod"/><path class="iuszqrjvz"/><path class="qz4brhaoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-alert-20" {...props}></Icon>
