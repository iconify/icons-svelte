<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq_9v787t.css';
import '../../css/v/vp-9qc54u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eq_9v787t"/><path class="vp-9qc54u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:ambulance" {...props}></Icon>
