<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnw8mlsse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnw8mlsse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:doctrine" {...props}></Icon>
