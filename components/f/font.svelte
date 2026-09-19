<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guvcc35_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="guvcc35_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:font" {...props}></Icon>
