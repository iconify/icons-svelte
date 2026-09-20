<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcg1jjb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hcg1jjb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:layout-pages-grid-16" {...props}></Icon>
