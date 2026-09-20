<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/m/m5-j3h.css';
import '../../css/b/btpiks.css';
import '../../css/s/so-from-40.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c m5-j3h"/><path class="a0m25c btpiks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:roundabout-right" {...props}></Icon>
