<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ebc18_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ebc18_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-dollar-2-fill" {...props}></Icon>
