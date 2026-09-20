<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9ex8-brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9ex8-brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clock-square-bold" {...props}></Icon>
