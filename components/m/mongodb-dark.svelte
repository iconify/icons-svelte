<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2q2m2bhm.css';
import '../../css/l/lt60qtbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k2q2m2bhm"/><path class="lt60qtbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mongodb-dark" {...props}></Icon>
