<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqgq8bbqo.css';
import '../../css/k/kys9qibdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="pqgq8bbqo"/><path class="kys9qibdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:comment-minus" {...props}></Icon>
