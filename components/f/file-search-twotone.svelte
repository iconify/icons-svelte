<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/q/qozz9v.css';
import '../../css/p/p9dchw.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew qozz9v"/><path class="iw1iew p9dchw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:file-search-twotone" {...props}></Icon>
