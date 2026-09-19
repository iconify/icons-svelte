<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_4k6nfuz.css';
import '../../css/e/e05dbabmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_4k6nfuz"/><path class="e05dbabmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:beach" {...props}></Icon>
