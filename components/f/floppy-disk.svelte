<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k804_rb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="k804_rb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:floppy-disk" {...props}></Icon>
