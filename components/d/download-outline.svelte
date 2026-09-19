<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpgikrbsr.css';
import '../../css/g/glc-ykbgi.css';
import '../../css/o/oehlnsb9i.css';
import '../../css/v/viqlb4bup.css';
import '../../css/w/woc15gb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="lpgikrbsr"/><rect transform="rotate(-90 5 18)" class="glc-ykbgi"/><rect transform="rotate(-90 19 18)" class="oehlnsb9i"/><path class="viqlb4bup"/><path class="woc15gb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:download-outline" {...props}></Icon>
