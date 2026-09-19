<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8h-plspy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g8h-plspy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:database" {...props}></Icon>
