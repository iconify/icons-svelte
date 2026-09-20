<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkpdcdh3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkpdcdh3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:keenetic" {...props}></Icon>
