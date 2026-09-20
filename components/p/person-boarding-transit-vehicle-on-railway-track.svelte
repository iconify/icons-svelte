<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imlbbu66u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="imlbbu66u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-boarding-transit-vehicle-on-railway-track" {...props}></Icon>
