<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn4d29b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bn4d29b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-left-up-20-solid" {...props}></Icon>
