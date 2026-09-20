<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuw044e9p.css';
import '../../css/g/ghm7_z0ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nuw044e9p"/><path class="ghm7_z0ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:layout-pages-wrap-16" {...props}></Icon>
