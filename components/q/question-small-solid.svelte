<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdryi132l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hdryi132l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:question-small-solid" {...props}></Icon>
