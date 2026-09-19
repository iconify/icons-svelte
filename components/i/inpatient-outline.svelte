<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2k7pibuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o2k7pibuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:inpatient-outline" {...props}></Icon>
