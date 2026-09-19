<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8vgp4bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":7};
const content = `<path class="b8vgp4bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:down" {...props}></Icon>
