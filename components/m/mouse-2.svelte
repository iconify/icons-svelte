<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmjyrqbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmjyrqbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mouse-2" {...props}></Icon>
