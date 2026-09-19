<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltnkflbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ltnkflbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bell-fill" {...props}></Icon>
