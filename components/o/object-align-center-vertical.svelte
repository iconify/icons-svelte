<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjv45ilyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fjv45ilyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:object-align-center-vertical" {...props}></Icon>
