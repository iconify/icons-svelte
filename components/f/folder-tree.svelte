<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/g/g1uu0n5gk.css';
import '../../css/y/yxcd2-bjp.css';
import '../../css/u/uhzeogauj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="g1uu0n5gk"/><path class="yxcd2-bjp"/><path class="uhzeogauj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:folder-tree" {...props}></Icon>
