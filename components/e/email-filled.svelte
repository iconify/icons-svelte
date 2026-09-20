<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_amxs.css';
import '../../css/a/a0m25c.css';
import '../../css/l/lew-ud.css';
import '../../css/l/lufy5p.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_amxs"/><path class="a0m25c lew-ud"/><path class="a0m25c lufy5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:email-filled" {...props}></Icon>
