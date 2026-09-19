<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoz51dbyx.css';
import '../../css/r/r_b7lhsan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hoz51dbyx"/><path class="r_b7lhsan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:price-tag-alt" {...props}></Icon>
