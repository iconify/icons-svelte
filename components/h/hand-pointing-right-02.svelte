<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okpmnqlhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okpmnqlhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hand-pointing-right-02" {...props}></Icon>
