<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg0p46jjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg0p46jjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:magic-wand-2" {...props}></Icon>
