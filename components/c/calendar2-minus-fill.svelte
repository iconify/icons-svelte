<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znt2fn3zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="znt2fn3zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar2-minus-fill" {...props}></Icon>
