<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehcglda7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehcglda7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:codeship" {...props}></Icon>
