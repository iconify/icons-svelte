<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbigfv4ml.css';
import '../../css/b/b7y_ypb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pbigfv4ml"/><path class="b7y_ypb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-refresh" {...props}></Icon>
