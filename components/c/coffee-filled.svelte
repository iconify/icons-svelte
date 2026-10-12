<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjg-q19wd.css';
import '../../css/e/eqdi4qwvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vjg-q19wd"/><path class="eqdi4qwvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:coffee-filled" {...props}></Icon>
