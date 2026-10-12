<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlb3uob7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tlb3uob7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-box-right-20" {...props}></Icon>
