<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsq9f2bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="tsq9f2bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:play-circle-solid" {...props}></Icon>
