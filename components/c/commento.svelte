<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kog5zicjb.css';
import '../../css/q/q3ko5nmxb.css';
import '../../css/o/o06rrkwts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="kog5zicjb"/><path class="q3ko5nmxb"/><path class="o06rrkwts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:commento" {...props}></Icon>
