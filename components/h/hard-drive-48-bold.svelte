<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu9rvubvf.css';
import '../../css/q/qauntjblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qu9rvubvf"/><path class="qauntjblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hard-drive-48-bold" {...props}></Icon>
