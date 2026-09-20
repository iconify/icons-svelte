<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t382k66tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="t382k66tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gui" {...props}></Icon>
