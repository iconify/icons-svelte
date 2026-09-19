<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a669i7b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a669i7b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:more-horiz" {...props}></Icon>
