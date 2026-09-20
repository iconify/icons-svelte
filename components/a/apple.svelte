<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjvs6cczp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3.5,"top":-2};
const content = `<path class="wjvs6cczp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:apple" {...props}></Icon>
