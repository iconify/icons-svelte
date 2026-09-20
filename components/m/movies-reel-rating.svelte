<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/id5b96b_s.css';
import '../../css/q/qvhu7ob2r.css';
import '../../css/b/b1dzrsyqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="id5b96b_s"/><path class="qvhu7ob2r"/><path class="b1dzrsyqb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:movies-reel-rating" {...props}></Icon>
