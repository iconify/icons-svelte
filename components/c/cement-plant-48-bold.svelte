<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7lngpy8k.css';
import '../../css/o/oid3f0gyj.css';
import '../../css/i/ihmii9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y7lngpy8k"/><path class="oid3f0gyj"/><path class="ihmii9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cement-plant-48-bold" {...props}></Icon>
