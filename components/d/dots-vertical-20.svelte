<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7kavpdpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o7kavpdpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:dots-vertical-20" {...props}></Icon>
