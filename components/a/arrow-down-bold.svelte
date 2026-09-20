<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7dywj58f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7dywj58f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-down-bold" {...props}></Icon>
