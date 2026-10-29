<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j896-2bez.css';
import '../../css/t/t066wzbea.css';
import '../../css/h/hrdjp705l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j896-2bez wm-k"/><path class="t066wzbea wm-a"/><path class="hrdjp705l wm-deco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:rotate-cw" {...props}></Icon>
