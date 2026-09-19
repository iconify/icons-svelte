<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbmn2oygh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":9,"height":16};
const content = `<path class="zbmn2oygh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:caretright" {...props}></Icon>
