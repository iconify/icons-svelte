<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obrfdl0hq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="obrfdl0hq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hospice" {...props}></Icon>
