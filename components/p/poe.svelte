<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvwtus5-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvwtus5-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:poe" {...props}></Icon>
