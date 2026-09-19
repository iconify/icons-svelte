<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boeyg5zgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boeyg5zgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:radio-circle" {...props}></Icon>
