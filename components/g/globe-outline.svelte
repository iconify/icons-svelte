<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hof09nbzk.css';
import '../../css/t/t42cy5box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hof09nbzk"/><path clip-rule="evenodd" class="t42cy5box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:globe-outline" {...props}></Icon>
