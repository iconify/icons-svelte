<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8rd68b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j8rd68b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:grooveshark" {...props}></Icon>
