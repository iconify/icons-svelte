<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/u/u-wsh989r.css';
import '../../css/o/ozd7kohpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<g class="to-5kdesz"><path class="u-wsh989r"/><path class="ozd7kohpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:nuxtjs-outline" {...props}></Icon>
