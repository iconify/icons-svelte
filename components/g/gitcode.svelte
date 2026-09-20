<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd1fl0qyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd1fl0qyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gitcode" {...props}></Icon>
