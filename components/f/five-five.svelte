<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4z4-ob1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y4z4-ob1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:five-five" {...props}></Icon>
