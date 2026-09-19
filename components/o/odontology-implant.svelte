<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me19hccys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="me19hccys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:odontology-implant" {...props}></Icon>
