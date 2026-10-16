<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naqry0ggt.css';
import '../../css/o/olslqwbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="naqry0ggt"/><path class="olslqwbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:humidifier-48" {...props}></Icon>
