<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc3ufsb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sc3ufsb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:list" {...props}></Icon>
