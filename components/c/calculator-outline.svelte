<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8cqm23rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p8cqm23rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:calculator-outline" {...props}></Icon>
