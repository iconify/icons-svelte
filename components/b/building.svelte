<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/armvf4bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="armvf4bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:building" {...props}></Icon>
