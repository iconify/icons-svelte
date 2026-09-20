<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/had-semte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="had-semte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:projector-screen-solid" {...props}></Icon>
