<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sot6zfbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sot6zfbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:creative-commons-by" {...props}></Icon>
