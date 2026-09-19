<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-hn1_blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-hn1_blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:linkedin" {...props}></Icon>
