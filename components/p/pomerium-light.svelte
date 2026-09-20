<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inemvmb9i.css';
import '../../css/u/u1l779tda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="inemvmb9i"/><path class="u1l779tda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pomerium-light" {...props}></Icon>
