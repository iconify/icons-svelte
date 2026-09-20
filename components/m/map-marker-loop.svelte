<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbheak.css';
import '../../css/l/lb41ec.css';
import '../../css/s/so-from-48.css';
import '../../css/t/tr-7ecuqx.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbheak"/><circle class="lb41ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:map-marker-loop" {...props}></Icon>
