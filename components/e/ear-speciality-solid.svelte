<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wraso3b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wraso3b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:ear-speciality-solid" {...props}></Icon>
