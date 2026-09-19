<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp06m64up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cp06m64up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-uturn-cw-left" {...props}></Icon>
