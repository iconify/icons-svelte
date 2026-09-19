<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud6fnccuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ud6fnccuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:align-top" {...props}></Icon>
