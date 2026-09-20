<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwu0driof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwu0driof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:card-add-1" {...props}></Icon>
