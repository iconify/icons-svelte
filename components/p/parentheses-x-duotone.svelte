<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz8yk_b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz8yk_b3a primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:parentheses-x-duotone" {...props}></Icon>
