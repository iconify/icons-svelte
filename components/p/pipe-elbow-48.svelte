<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur1gjzh2v.css';
import '../../css/u/uaklp-bbr.css';
import '../../css/e/ekmag7bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ur1gjzh2v"/><path class="uaklp-bbr"/><path class="ekmag7bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-elbow-48" {...props}></Icon>
