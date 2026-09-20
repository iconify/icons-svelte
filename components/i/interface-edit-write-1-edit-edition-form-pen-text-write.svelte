<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8qxkjbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w8qxkjbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-write-1-edit-edition-form-pen-text-write" {...props}></Icon>
