<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exy73hpiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="exy73hpiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-chevron-left" {...props}></Icon>
