<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe1_3nbpy.css';
import '../../css/g/ga0a0lbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":54,"height":100};
const content = `<path class="xe1_3nbpy"/><path class="ga0a0lbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-ui:android" {...props}></Icon>
