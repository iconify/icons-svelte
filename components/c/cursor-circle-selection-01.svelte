<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2o_zuh-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2o_zuh-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cursor-circle-selection-01" {...props}></Icon>
