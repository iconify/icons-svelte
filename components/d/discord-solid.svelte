<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx0m9s7_b.css';
import '../../css/i/igandw20i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wx0m9s7_b"/><path clip-rule="evenodd" class="igandw20i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:discord-solid" {...props}></Icon>
