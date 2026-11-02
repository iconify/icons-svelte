<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_h5l6mzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_h5l6mzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-won-2-fill" {...props}></Icon>
