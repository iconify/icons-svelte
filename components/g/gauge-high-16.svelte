<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td8i4ib_z.css';
import '../../css/b/bxw0pccgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="td8i4ib_z"/><path class="bxw0pccgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gauge-high-16" {...props}></Icon>
