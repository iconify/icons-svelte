<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glpy9wu7t.css';
import '../../css/t/tr_qzvbuu.css';
import '../../css/f/fd6xyabdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="glpy9wu7t"><path class="tr_qzvbuu"/><circle class="fd6xyabdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:lable-duotone" {...props}></Icon>
