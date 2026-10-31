<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/l1cpr8bjj.css';
import '../../css/k/k1pmlf02a.css';
import '../../css/n/n1y1i5mpe.css';
import '../../css/o/o2n2poguz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="l1cpr8bjj wm-shadow"/><path class="k1pmlf02a wm-shadow"/><path class="n1y1i5mpe"/><path class="o2n2poguz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:cloud-hail" {...props}></Icon>
