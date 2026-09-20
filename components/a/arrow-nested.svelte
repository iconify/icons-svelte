<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqmbhv_3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqmbhv_3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-nested" {...props}></Icon>
