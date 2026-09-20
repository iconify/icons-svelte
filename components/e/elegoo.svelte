<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-2sbm6kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-2sbm6kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:elegoo" {...props}></Icon>
