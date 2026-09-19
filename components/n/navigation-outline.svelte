<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkb7h_7ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkb7h_7ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:navigation-outline" {...props}></Icon>
