<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jv0tnvh6k.css';
import '../../css/k/ko4diswnn.css';
import '../../css/g/ggbkigbor.css';
import '../../css/c/cbce2qkkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jv0tnvh6k"/><path class="ko4diswnn"/><path class="ggbkigbor"/><path class="cbce2qkkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:modern-camera-go-pro" {...props}></Icon>
