<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-b_zxyms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="x-b_zxyms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:call-in-26" {...props}></Icon>
