<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lejn1miiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lejn1miiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-scrambling-on-cliff-wearing-backpack" {...props}></Icon>
