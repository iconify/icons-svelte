<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmzxt7bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hmzxt7bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:network-16" {...props}></Icon>
