<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o08a26b7z.css';
import '../../css/j/j-jecncax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o08a26b7z"/><path clip-rule="evenodd" class="j-jecncax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aihubmix" {...props}></Icon>
