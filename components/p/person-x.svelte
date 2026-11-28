<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlts9hb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlts9hb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:person-x" {...props}></Icon>
