<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d4zhwxbde.css';
import '../../css/t/tg8emrdzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d4zhwxbde"/><path clip-rule="evenodd" class="tg8emrdzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:archive-box-flat" {...props}></Icon>
