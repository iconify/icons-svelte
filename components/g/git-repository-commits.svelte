<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p07tmccvv.css';
import '../../css/f/fxuspib9g.css';
import '../../css/s/svp7he8me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="p07tmccvv"><path class="fxuspib9g"/><path class="svp7he8me"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:git-repository-commits" {...props}></Icon>
