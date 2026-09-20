<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x85ogmb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x85ogmb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clock-circle-outline" {...props}></Icon>
