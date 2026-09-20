<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9hubmb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a9hubmb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:atm-text" {...props}></Icon>
