<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlfswok4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tlfswok4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:certified-filled-16" {...props}></Icon>
