<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0knyqbyx.css';
import '../../css/z/zoxpwbb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g0knyqbyx"/><path class="zoxpwbb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:package-plus-filled" {...props}></Icon>
