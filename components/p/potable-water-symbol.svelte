<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrd-cjyhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zrd-cjyhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:potable-water-symbol" {...props}></Icon>
