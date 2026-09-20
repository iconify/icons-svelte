<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/f/fkvl2c.css';
import '../../css/k/k_e22n.css';
import '../../css/s/so-from-14.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c fkvl2c"/><path class="a0m25c k_e22n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrows-horizontal-alt" {...props}></Icon>
