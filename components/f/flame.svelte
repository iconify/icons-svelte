<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7u52s0kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g7u52s0kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:flame" {...props}></Icon>
