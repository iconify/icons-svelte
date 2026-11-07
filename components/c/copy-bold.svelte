<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt0ievjnc.css';
import '../../css/n/nazq8_bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt0ievjnc"/><path class="nazq8_bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-bold" {...props}></Icon>
