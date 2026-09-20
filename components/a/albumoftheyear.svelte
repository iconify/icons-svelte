<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enwul_-6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enwul_-6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:albumoftheyear" {...props}></Icon>
