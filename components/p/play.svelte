<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc2v17baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sc2v17baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:play" {...props}></Icon>
