<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb95-1bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jb95-1bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:building-office-20-solid" {...props}></Icon>
