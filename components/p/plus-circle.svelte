<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfywoom4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="kfywoom4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:plus-circle" {...props}></Icon>
