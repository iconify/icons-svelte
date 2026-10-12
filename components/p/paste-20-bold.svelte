<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0ne4_zha.css';
import '../../css/a/appx2gb4r.css';
import '../../css/e/em0ki7-fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k0ne4_zha"/><path class="appx2gb4r"/><path class="em0ki7-fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paste-20-bold" {...props}></Icon>
