<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlhwvygnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dlhwvygnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:rectangle-stack-20-solid" {...props}></Icon>
