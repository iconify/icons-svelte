<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpeepxwiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1217,"height":1000};
const content = `<path class="zpeepxwiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:archive" {...props}></Icon>
