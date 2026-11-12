<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8s2800fo.css';
import '../../css/m/ma-2opx8e.css';
import '../../css/u/uruqrcc2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n8s2800fo"/><path class="ma-2opx8e"/><path class="uruqrcc2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netflix" {...props}></Icon>
