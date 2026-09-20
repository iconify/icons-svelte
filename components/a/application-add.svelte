<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqbub0eaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqbub0eaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:application-add" {...props}></Icon>
