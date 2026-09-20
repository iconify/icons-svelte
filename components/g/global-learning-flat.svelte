<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/onoh73b6l.css';
import '../../css/v/v42xnhcko.css';
import '../../css/d/d59qf6ssp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="onoh73b6l"/><path class="v42xnhcko"/><path class="d59qf6ssp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:global-learning-flat" {...props}></Icon>
