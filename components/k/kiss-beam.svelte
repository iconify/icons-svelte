<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc5h94boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="sc5h94boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:kiss-beam" {...props}></Icon>
