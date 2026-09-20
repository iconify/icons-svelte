<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gofrvbhmp.css';
import '../../css/d/d9nzp3e2z.css';
import '../../css/z/zcsc2k1xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gofrvbhmp"/><path class="d9nzp3e2z"/><path class="zcsc2k1xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:podcast-solid" {...props}></Icon>
