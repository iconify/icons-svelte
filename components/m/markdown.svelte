<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpp8vfq_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpp8vfq_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:markdown" {...props}></Icon>
