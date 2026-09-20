<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o86pnqbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o86pnqbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-right-fill" {...props}></Icon>
