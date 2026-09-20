<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbnbyk57b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbnbyk57b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:compass-big-outline" {...props}></Icon>
