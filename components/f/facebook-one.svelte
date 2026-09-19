<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s1hkfdcbz.css';
import '../../css/u/u5n_y8b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s1hkfdcbz"/><path class="u5n_y8b6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:facebook-one" {...props}></Icon>
