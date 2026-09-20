<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4hduvb-v.css';
import '../../css/p/ppwhpebbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j4hduvb-v"/><path clip-rule="evenodd" class="ppwhpebbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:eslint-solid" {...props}></Icon>
