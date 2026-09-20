<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq56kppzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fq56kppzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:account-logout" {...props}></Icon>
