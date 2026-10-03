<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjfaz3b4o.css';
import '../../css/c/c12j9pbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":194.955};
const content = `<path class="yjfaz3b4o"/><path class="c12j9pbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:citibank" {...props}></Icon>
