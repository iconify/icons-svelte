<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6g4cmbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x6g4cmbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:baby-bottle" {...props}></Icon>
