<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm81jd_my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm81jd_my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:anchor" {...props}></Icon>
