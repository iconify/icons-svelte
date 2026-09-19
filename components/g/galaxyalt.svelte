<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guan1wbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="guan1wbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:galaxyalt" {...props}></Icon>
