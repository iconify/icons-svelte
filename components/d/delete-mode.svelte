<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7g8vpbdo.css';
import '../../css/t/twovfhblf.css';
import '../../css/o/oi613jb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l7g8vpbdo"><path class="twovfhblf"/><path class="oi613jb8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:delete-mode" {...props}></Icon>
