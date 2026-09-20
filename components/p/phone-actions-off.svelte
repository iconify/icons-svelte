<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q1nhjcbcq.css';
import '../../css/p/p3h83ob2l.css';
import '../../css/n/nlk--ac8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q1nhjcbcq"/><path class="p3h83ob2l"/><path class="nlk--ac8v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:phone-actions-off" {...props}></Icon>
