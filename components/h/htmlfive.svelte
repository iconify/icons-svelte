<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgxn-yw5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="hgxn-yw5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:htmlfive" {...props}></Icon>
