<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vczu8bbqb.css';
import '../../css/i/im-u2lvxf.css';
import '../../css/h/htbq12b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vczu8bbqb"/><path class="im-u2lvxf"/><path class="htbq12b0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:globe-x-duotone" {...props}></Icon>
