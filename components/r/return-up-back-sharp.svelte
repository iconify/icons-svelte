<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhqdc85vd.css';
import '../../css/c/ceke74b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vhqdc85vd"/><path class="ceke74b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:return-up-back-sharp" {...props}></Icon>
