<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk4cjeb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk4cjeb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:microdotblog" {...props}></Icon>
