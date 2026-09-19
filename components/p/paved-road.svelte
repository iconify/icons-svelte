<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdrra_btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gdrra_btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:paved-road" {...props}></Icon>
