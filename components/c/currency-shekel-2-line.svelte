<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymceq9b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymceq9b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-shekel-2-line" {...props}></Icon>
