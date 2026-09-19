<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2pqswazu.css';
import '../../css/w/ww4fyqbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q2pqswazu"/><path class="ww4fyqbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:checkmark-outline" {...props}></Icon>
