<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/facd9-b5n.css';
import '../../css/g/gb2byyq8r.css';
import '../../css/d/df6h5iboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="facd9-b5n"/><path class="gb2byyq8r"/><path class="df6h5iboy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:closet2-duotone" {...props}></Icon>
