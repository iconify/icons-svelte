<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucomdgbea.css';
import '../../css/m/m9uodidsu.css';
import '../../css/w/wx7rgmjkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="ucomdgbea"/><path class="m9uodidsu"/><circle class="wx7rgmjkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyxiontech-pdf-tools" {...props}></Icon>
