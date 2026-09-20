<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bjxt11j3n.css';
import '../../css/k/kmejg72ch.css';
import '../../css/k/kkj8cetyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bjxt11j3n"/><path clip-rule="evenodd" class="kmejg72ch"/><path class="kkj8cetyt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:atom-filled" {...props}></Icon>
