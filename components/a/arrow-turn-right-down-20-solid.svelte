<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqxmgob4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fqxmgob4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-right-down-20-solid" {...props}></Icon>
