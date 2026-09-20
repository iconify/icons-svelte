<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crs9g4qvt.css';
import '../../css/f/fbk-2ebdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crs9g4qvt"/><path clip-rule="evenodd" class="fbk-2ebdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-boolean-duotone" {...props}></Icon>
