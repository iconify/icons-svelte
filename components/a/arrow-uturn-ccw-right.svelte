<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm9im5b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qm9im5b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-uturn-ccw-right" {...props}></Icon>
