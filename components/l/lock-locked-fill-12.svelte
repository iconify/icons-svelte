<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r30t8djrj.css';
import '../../css/b/b-ejs9bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="r30t8djrj"/><rect class="b-ejs9bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lock-locked-fill-12" {...props}></Icon>
