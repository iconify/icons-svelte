<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npdp7k8ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npdp7k8ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:remove-circle" {...props}></Icon>
