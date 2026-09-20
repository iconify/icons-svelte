<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giwee0bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="giwee0bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:hammer-shoe" {...props}></Icon>
