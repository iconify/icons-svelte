<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k863ckb4g.css';
import '../../css/l/l5ybookek.css';
import '../../css/s/sqn_l5bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k863ckb4g"/><path class="l5ybookek"/><path class="sqn_l5bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-elbow-20" {...props}></Icon>
