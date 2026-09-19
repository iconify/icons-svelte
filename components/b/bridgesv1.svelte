<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqer2gnrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqer2gnrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bridgesv1" {...props}></Icon>
