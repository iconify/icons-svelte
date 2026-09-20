<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2-9wig_g.css';
import '../../css/k/kow831b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2-9wig_g"/><path class="kow831b3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:briefcase-medical-duotone" {...props}></Icon>
