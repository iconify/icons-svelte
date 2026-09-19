<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbgqw50ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tbgqw50ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:balloon" {...props}></Icon>
