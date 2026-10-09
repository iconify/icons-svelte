<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb7o8wq_f.css';
import '../../css/v/vh4ifyb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gb7o8wq_f"/><path class="vh4ifyb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:contract-48-bold" {...props}></Icon>
