<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d47xi2b9o.css';
import '../../css/b/bkpb9nbrp.css';
import '../../css/t/t47_ldbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="bkpb9nbrp"/><path class="t47_ldbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:pound" {...props}></Icon>
