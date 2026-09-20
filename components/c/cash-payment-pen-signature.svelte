<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nor1toeqo.css';
import '../../css/e/ez1w0xblt.css';
import '../../css/q/q3-zht3yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nor1toeqo"/><path class="ez1w0xblt"/><path class="q3-zht3yu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cash-payment-pen-signature" {...props}></Icon>
