<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2jgkrbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f2jgkrbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:card-heart" {...props}></Icon>
