<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wbygb0tnm.css';
import '../../css/l/ly0q5ab1k.css';
import '../../css/e/ecmm5nb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wbygb0tnm"/><path class="ly0q5ab1k"/><path class="ecmm5nb_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:crypto-close-up-group-chat-users-conversation" {...props}></Icon>
