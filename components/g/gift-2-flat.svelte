<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fezqjvb_n.css';
import '../../css/j/jgjb6qb6r.css';
import '../../css/r/rsuw5wndk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fezqjvb_n"/><path class="jgjb6qb6r"/><path class="rsuw5wndk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:gift-2-flat" {...props}></Icon>
