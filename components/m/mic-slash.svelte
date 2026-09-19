<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_0pz_gks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="k_0pz_gks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:mic-slash" {...props}></Icon>
