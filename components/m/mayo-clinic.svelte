<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug37mwq9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ug37mwq9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mayo-clinic" {...props}></Icon>
