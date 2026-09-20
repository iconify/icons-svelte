<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/x/xi5wq3t8b.css';
import '../../css/h/hqodx2bjc.css';
import '../../css/x/xehwz-biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="xi5wq3t8b"/><circle class="hqodx2bjc"/><path class="xehwz-biw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:question-duotone" {...props}></Icon>
