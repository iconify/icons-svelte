<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd9u0ph8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd9u0ph8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:rail-symbol" {...props}></Icon>
