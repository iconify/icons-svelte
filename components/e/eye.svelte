<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei5v8ab1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ei5v8ab1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:eye" {...props}></Icon>
