<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_1_g2krb.css';
import '../../css/o/o-tazueek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r_1_g2krb"/><path class="o-tazueek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cow-20" {...props}></Icon>
