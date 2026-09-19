<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdg1wsjbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sdg1wsjbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:nuls" {...props}></Icon>
