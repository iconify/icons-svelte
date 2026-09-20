<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbh-kn0cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mbh-kn0cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-and-person-riding-bicycle" {...props}></Icon>
