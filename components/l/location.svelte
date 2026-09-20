<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u148y6bbs.css';
import '../../css/a/az7uqpbwk.css';
import '../../css/y/y9-n05-_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="u148y6bbs"><path class="az7uqpbwk"/><path class="y9-n05-_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:location" {...props}></Icon>
