<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acjrvm-jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="acjrvm-jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-down-left-20-solid" {...props}></Icon>
