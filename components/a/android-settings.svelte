<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xpj4vkbbe.css';
import '../../css/l/lohd83bha.css';
import '../../css/r/rpk44qb5q.css';
import '../../css/o/ouzjljbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xpj4vkbbe"/><path class="lohd83bha"/><path class="rpk44qb5q"/><path class="ouzjljbfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:android-settings" {...props}></Icon>
