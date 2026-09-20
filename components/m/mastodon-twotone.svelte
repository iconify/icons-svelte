<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/w/wm-m9w.css';
import '../../css/l/ljka7g.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-82.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew wm-m9w"/><path class="iw1iew ljka7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:mastodon-twotone" {...props}></Icon>
