<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk4m4tjvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="hk4m4tjvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:heartsparkle" {...props}></Icon>
