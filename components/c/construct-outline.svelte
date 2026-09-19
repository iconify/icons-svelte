<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7kg3hbvs.css';
import '../../css/i/irdc55aqf.css';
import '../../css/d/di4jzbbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o7kg3hbvs"/><path class="irdc55aqf"/><path class="di4jzbbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:construct-outline" {...props}></Icon>
