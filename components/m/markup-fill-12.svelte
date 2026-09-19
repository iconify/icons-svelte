<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bowbitjld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bowbitjld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:markup-fill-12" {...props}></Icon>
