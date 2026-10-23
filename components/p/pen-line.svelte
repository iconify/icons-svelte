<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnzilfbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnzilfbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pen-line" {...props}></Icon>
