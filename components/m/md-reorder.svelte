<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_4zw6myr.css';
import '../../css/d/dqmrp9wad.css';
import '../../css/k/ksly09b8o.css';
import '../../css/b/bl5cpf6bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_4zw6myr"/><path class="dqmrp9wad"/><path class="ksly09b8o"/><path class="bl5cpf6bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-reorder" {...props}></Icon>
