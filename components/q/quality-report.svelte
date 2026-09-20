<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-mv4pbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p-mv4pbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:quality-report" {...props}></Icon>
