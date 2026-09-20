<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5amaac0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="q5amaac0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-vertical-solid" {...props}></Icon>
