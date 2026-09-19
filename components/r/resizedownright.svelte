<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd-mgyb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hd-mgyb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:resizedownright" {...props}></Icon>
