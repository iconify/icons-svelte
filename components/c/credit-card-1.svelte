<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rodx-bbgi.css';
import '../../css/u/usszxechu.css';
import '../../css/y/yxybwwqbg.css';
import '../../css/u/u6wus0bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rodx-bbgi"/><path class="usszxechu"/><path class="yxybwwqbg"/><path class="u6wus0bjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:credit-card-1" {...props}></Icon>
