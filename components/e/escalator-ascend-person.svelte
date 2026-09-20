<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o58aldlyn.css';
import '../../css/p/pai9iqpjo.css';
import '../../css/p/p7m0yt11w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o58aldlyn"/><path class="pai9iqpjo"/><path class="p7m0yt11w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:escalator-ascend-person" {...props}></Icon>
