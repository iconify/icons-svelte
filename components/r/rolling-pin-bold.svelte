<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttg6ivr-q.css';
import '../../css/k/k0g8rv05t.css';
import '../../css/a/ahhagtoge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttg6ivr-q"/><path class="k0g8rv05t"/><path class="ahhagtoge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rolling-pin-bold" {...props}></Icon>
