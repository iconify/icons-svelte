<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwk_1c3ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lwk_1c3ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:campingcar" {...props}></Icon>
