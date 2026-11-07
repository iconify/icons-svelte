<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmcdlcbwt.css';
import '../../css/j/jyt8hmbvk.css';
import '../../css/g/g57wd6_qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmcdlcbwt"/><path class="jyt8hmbvk"/><path class="g57wd6_qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mug-bold" {...props}></Icon>
