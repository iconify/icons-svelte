<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjq2w1_ae.css';
import '../../css/n/nbgk0wbrq.css';
import '../../css/d/dj35aibbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjq2w1_ae"/><path class="nbgk0wbrq"/><path class="dj35aibbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:people-nearby-bold-duotone" {...props}></Icon>
