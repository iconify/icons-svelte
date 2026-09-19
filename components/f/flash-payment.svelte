<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/j/j657_1wqq.css';
import '../../css/o/o5g359bjg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGopdtwbIm"><g class="hv130ab-t"><path class="j657_1wqq"/><path class="o5g359bjg"/></g></mask></defs><path mask="url(#SVGopdtwbIm)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:flash-payment" {...props}></Icon>
