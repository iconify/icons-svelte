<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl16mfhuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xl16mfhuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layout-list-20-bold" {...props}></Icon>
