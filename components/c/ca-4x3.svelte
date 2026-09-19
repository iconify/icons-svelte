<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqz-ogqhl.css';
import '../../css/a/a2nfcgrow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="eqz-ogqhl"/><path class="a2nfcgrow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ca-4x3" {...props}></Icon>
