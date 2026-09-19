<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5h7chj0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5h7chj0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:book" {...props}></Icon>
