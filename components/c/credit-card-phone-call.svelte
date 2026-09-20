<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cuts94bpt.css';
import '../../css/r/rv7ziu97u.css';
import '../../css/e/ezfkwpbnf.css';
import '../../css/v/vk5jjex7q.css';
import '../../css/i/ib8ttcbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="cuts94bpt"/><path class="rv7ziu97u"/><path class="ezfkwpbnf"/><path class="vk5jjex7q"/><path class="ib8ttcbir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:credit-card-phone-call" {...props}></Icon>
