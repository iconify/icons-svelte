<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm48-6mzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm48-6mzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:currency-dollar-circle" {...props}></Icon>
