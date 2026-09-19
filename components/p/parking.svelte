<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tae50hpaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":280,"height":384};
const content = `<path class="tae50hpaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:parking" {...props}></Icon>
