<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/x/x6dwuo.css';
import '../../css/a/ahcaho.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-50.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew x6dwuo"/><path class="ahcaho iw1iew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:laptop-twotone" {...props}></Icon>
