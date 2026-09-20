<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqn5az9ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqn5az9ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:gender-female" {...props}></Icon>
