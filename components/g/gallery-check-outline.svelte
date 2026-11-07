<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vognngb9s.css';
import '../../css/g/gzhk0bblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vognngb9s"/><path class="gzhk0bblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-check-outline" {...props}></Icon>
