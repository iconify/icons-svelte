<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkti4bbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xkti4bbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gatsbyjs-solid" {...props}></Icon>
