<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-uoebctb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="f-uoebctb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:image-slash-fill" {...props}></Icon>
