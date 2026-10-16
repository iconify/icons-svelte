<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkjsbignm.css';
import '../../css/f/fkpmaxbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dkjsbignm"/><path class="fkpmaxbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:glacier-48-bold" {...props}></Icon>
