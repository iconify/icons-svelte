<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xw5oxouqi.css';
import '../../css/p/p4m9i4bbw.css';
import '../../css/n/n7dpi5bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xw5oxouqi"/><path class="p4m9i4bbw"/><path class="n7dpi5bvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-check-fill" {...props}></Icon>
