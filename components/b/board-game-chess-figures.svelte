<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/djdh_3b6t.css';
import '../../css/o/ocbknsu8a.css';
import '../../css/f/fuwf3cc6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="djdh_3b6t"/><path class="ocbknsu8a"/><path class="fuwf3cc6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:board-game-chess-figures" {...props}></Icon>
