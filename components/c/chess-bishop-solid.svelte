<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc8awf2mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc8awf2mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chess-bishop-solid" {...props}></Icon>
