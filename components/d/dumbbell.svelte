<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo7xx-bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bo7xx-bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:dumbbell" {...props}></Icon>
