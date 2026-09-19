<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4o7a5b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d4o7a5b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:magic-wand" {...props}></Icon>
