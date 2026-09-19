<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjy8i0bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fjy8i0bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:box" {...props}></Icon>
