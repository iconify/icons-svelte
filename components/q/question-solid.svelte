<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia85dv29k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ia85dv29k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:question-solid" {...props}></Icon>
