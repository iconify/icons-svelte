<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kyoivpb1v.css';
import '../../css/y/y84sanbev.css';
import '../../css/s/s_ax9mbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="kyoivpb1v"/><path class="y84sanbev"/><path class="s_ax9mbxh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:notes-quill" {...props}></Icon>
