<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pom5f7b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pom5f7b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hard-hat-filled" {...props}></Icon>
