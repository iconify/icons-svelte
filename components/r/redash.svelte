<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7ocqh3rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7ocqh3rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:redash" {...props}></Icon>
