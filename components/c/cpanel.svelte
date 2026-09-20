<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brmk2qfek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":407.66,"height":240};
const content = `<path class="brmk2qfek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cpanel" {...props}></Icon>
