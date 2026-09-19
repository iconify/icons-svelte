<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8e9n1-iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="w8e9n1-iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:grid-add-26" {...props}></Icon>
