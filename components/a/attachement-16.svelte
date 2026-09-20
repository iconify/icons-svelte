<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf1-a4a-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uf1-a4a-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:attachement-16" {...props}></Icon>
