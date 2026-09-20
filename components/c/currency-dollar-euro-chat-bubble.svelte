<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/za-y-u5-e.css';
import '../../css/p/pruluhbfg.css';
import '../../css/q/qhu_wpbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="za-y-u5-e"/><path class="pruluhbfg"/><path class="qhu_wpbju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:currency-dollar-euro-chat-bubble" {...props}></Icon>
