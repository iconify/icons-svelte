<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1sqqcc6o.css';
import '../../css/i/iwwx5ob6h.css';
import '../../css/c/c3vcymbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s1sqqcc6o"/><path class="iwwx5ob6h"/><path class="c3vcymbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-kpaste-light" {...props}></Icon>
