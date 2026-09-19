<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qflp29d0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qflp29d0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:peace" {...props}></Icon>
