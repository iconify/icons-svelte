<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc2fcx.css';
import '../../css/v/v1m4oy.css';
import '../../css/s/so-from-60.css';
import '../../css/d/d-6uh96y.css';
import '../../css/d/d-t2f-vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc2fcx"/><path class="v1m4oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:cloud-alt-upload" {...props}></Icon>
