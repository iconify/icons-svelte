<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgvdncbht.css';
import '../../css/s/sz375c7xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dgvdncbht"/><path class="sz375c7xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:camera" {...props}></Icon>
