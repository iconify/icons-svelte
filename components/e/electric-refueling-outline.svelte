<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha7uky3jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ha7uky3jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:electric-refueling-outline" {...props}></Icon>
