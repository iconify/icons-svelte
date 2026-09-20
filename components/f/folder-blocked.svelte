<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bf4v0abcn.css';
import '../../css/g/gmj67c7jw.css';
import '../../css/m/mgo8kyexx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bf4v0abcn"/><path class="gmj67c7jw"/><path class="mgo8kyexx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-blocked" {...props}></Icon>
