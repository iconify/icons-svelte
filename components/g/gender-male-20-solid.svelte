<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey4hq3keo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ey4hq3keo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-male-20-solid" {...props}></Icon>
