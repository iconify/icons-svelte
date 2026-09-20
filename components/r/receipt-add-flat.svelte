<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rm0pfvbgp.css';
import '../../css/u/uiksm4b9u.css';
import '../../css/y/yi1r2aben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="rm0pfvbgp"/><path clip-rule="evenodd" class="uiksm4b9u"/><path class="yi1r2aben"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:receipt-add-flat" {...props}></Icon>
