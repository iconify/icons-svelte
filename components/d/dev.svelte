<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj9mviyqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xj9mviyqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:dev" {...props}></Icon>
