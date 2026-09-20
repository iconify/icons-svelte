<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xjkn4dkhv.css';
import '../../css/l/lqbt8yntn.css';
import '../../css/h/huyefibpi.css';
import '../../css/u/u8i52477k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xjkn4dkhv"/><path class="lqbt8yntn"/><path class="huyefibpi"/><path class="u8i52477k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:accounting-invoice-mail" {...props}></Icon>
