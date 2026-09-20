<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urogpp.css';
import '../../css/a/a0m25c.css';
import '../../css/a/ae_viy.css';
import '../../css/c/cn_flp.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urogpp"/><path class="a0m25c ae_viy"/><path class="a0m25c cn_flp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:cloud-filled" {...props}></Icon>
