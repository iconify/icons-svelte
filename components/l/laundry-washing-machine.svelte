<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/oabrzubno.css';
import '../../css/s/s-0rvs0ec.css';
import '../../css/z/zruh-lbqh.css';
import '../../css/v/v0xg5qbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="oabrzubno"/><path class="s-0rvs0ec"/><path class="zruh-lbqh"/><path class="v0xg5qbry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:laundry-washing-machine" {...props}></Icon>
