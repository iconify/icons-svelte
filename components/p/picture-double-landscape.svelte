<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/l8ujfflzo.css';
import '../../css/y/ytamnattm.css';
import '../../css/e/emqs3cc7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="l8ujfflzo"/><path class="ytamnattm"/><path class="emqs3cc7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:picture-double-landscape" {...props}></Icon>
