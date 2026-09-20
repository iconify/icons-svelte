<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/x/xr5osn.css';
import '../../css/d/dsugin.css';
import '../../css/y/y4wbml.css';
import '../../css/g/g-mogd.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew xr5osn"/><path class="dsugin iw1iew y4wbml"/><path class="g-mogd iw1iew y4wbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:phone-incoming-filled" {...props}></Icon>
