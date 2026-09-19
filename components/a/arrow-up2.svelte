<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpb55zepl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jpb55zepl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:arrow-up2" {...props}></Icon>
