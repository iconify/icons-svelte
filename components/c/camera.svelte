<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfwxb5b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gfwxb5b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:camera" {...props}></Icon>
