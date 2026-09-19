<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvvcsfsvy.css';
import '../../css/t/ttnbi3byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvvcsfsvy"/><path clip-rule="evenodd" class="ttnbi3byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:battery-quarter-outline" {...props}></Icon>
