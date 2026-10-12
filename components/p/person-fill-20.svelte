<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz57ce9bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yz57ce9bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-fill-20" {...props}></Icon>
