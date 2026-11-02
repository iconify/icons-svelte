<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3anj3bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3anj3bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-horizontal-fill" {...props}></Icon>
