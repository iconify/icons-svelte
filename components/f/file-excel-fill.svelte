<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-fkrzt2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l-fkrzt2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-excel-fill" {...props}></Icon>
