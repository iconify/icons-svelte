<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjlu84bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kjlu84bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:mintbit" {...props}></Icon>
