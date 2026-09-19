<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf-zqubsq.css';
import '../../css/k/kb9hd4ajm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="cf-zqubsq"/><path class="kb9hd4ajm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:passport" {...props}></Icon>
