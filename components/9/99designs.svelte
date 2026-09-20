<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j37bt1bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j37bt1bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:99designs" {...props}></Icon>
