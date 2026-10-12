<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bkjebkkrm.css';
import '../../css/x/xsu2qyb6y.css';
import '../../css/h/hy9onbbxk.css';
import '../../css/a/aqv759fpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bkjebkkrm"/><path class="xsu2qyb6y"/><path class="hy9onbbxk"/><path class="aqv759fpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:files-duotone" {...props}></Icon>
