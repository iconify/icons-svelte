<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6-rcbv6t.css';
import '../../css/z/z8qts6bhu.css';
import '../../css/p/pgb6kxbaw.css';
import '../../css/a/am_oegbzf.css';
import '../../css/g/g776s3b5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x6-rcbv6t"/><path class="z8qts6bhu"/><path class="pgb6kxbaw"/><path class="am_oegbzf"/><path class="g776s3b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-solar-20" {...props}></Icon>
