<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbbfu8bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbbfu8bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:necktie" {...props}></Icon>
