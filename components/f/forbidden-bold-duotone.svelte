<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-lbvibdh.css';
import '../../css/i/i-d-6-4rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-lbvibdh"/><path class="i-d-6-4rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forbidden-bold-duotone" {...props}></Icon>
