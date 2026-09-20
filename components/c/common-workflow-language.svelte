<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs0u1_bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs0u1_bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:common-workflow-language" {...props}></Icon>
