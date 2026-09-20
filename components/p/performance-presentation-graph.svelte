<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r2a_pl06n.css';
import '../../css/p/plca6s4vd.css';
import '../../css/z/zr33v6yek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r2a_pl06n"/><path class="plca6s4vd"/><path class="zr33v6yek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:performance-presentation-graph" {...props}></Icon>
