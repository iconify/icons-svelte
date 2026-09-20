<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y3-abdj5w.css';
import '../../css/f/f9u-xt92m.css';
import '../../css/b/b8o1_sb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="y3-abdj5w"/><path class="f9u-xt92m"/><path class="b8o1_sb7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:bug-cloud-error" {...props}></Icon>
