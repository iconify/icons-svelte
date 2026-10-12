<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae9akljna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ae9akljna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:car-fill-20" {...props}></Icon>
