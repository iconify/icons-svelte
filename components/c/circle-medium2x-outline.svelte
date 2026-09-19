<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-qtcu_5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o-qtcu_5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:circle-medium2x-outline" {...props}></Icon>
