<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9822ynid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y9822ynid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:closed-book" {...props}></Icon>
