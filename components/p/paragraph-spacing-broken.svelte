<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/e55mrdbou.css';
import '../../css/b/bq0ypf47a.css';
import '../../css/i/iim04tfhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e55mrdbou"/><path class="bq0ypf47a"/><path class="iim04tfhn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paragraph-spacing-broken" {...props}></Icon>
