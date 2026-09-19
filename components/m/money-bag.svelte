<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg7r8vz2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fg7r8vz2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:money-bag" {...props}></Icon>
