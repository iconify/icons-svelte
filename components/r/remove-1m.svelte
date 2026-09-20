<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2brmfbab.css';
import '../../css/a/a3jz1tb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="b2brmfbab"/><path class="a3jz1tb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:remove-1m" {...props}></Icon>
