<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er6yahbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="er6yahbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-3-20-solid" {...props}></Icon>
