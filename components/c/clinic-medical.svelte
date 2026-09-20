<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pknpwpb5q.css';
import '../../css/l/l2nst-b0v.css';
import '../../css/k/ks5mnsbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pknpwpb5q"/><path class="l2nst-b0v"/><path class="ks5mnsbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:clinic-medical" {...props}></Icon>
