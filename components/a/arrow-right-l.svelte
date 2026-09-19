<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn-s6sfow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn-s6sfow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:arrow-right-l" {...props}></Icon>
