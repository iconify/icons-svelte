<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-d90l.css';
import '../../css/i/iw1iew.css';
import '../../css/f/fce2zc.css';
import '../../css/s/so-from-14.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-d90l iw1iew"/><path class="fce2zc iw1iew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:circle-twotone-to-confirm-circle-twotone-transition" {...props}></Icon>
