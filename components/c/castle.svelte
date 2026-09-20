<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiuykqbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="fiuykqbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:castle" {...props}></Icon>
