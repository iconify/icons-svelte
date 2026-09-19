<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn_xmxb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="kn_xmxb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:relationshape-support-26" {...props}></Icon>
