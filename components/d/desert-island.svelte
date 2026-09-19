<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd2ockczu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pd2ockczu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:desert-island" {...props}></Icon>
