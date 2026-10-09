<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0d-k9bod.css';
import '../../css/i/iuszqrjvz.css';
import '../../css/g/g3z_62mfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w0d-k9bod"/><path class="iuszqrjvz"/><path class="g3z_62mfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-check-20" {...props}></Icon>
