<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiscr4mes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fiscr4mes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:building-office" {...props}></Icon>
