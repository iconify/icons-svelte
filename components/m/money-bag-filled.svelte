<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6wdq4byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z6wdq4byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:money-bag-filled" {...props}></Icon>
