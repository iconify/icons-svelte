<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytff_t6vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ytff_t6vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-carrying-ski" {...props}></Icon>
