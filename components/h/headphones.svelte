<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_p9tyzab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_p9tyzab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:headphones" {...props}></Icon>
