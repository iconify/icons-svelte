<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa3ap3bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pa3ap3bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:factory" {...props}></Icon>
