<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6utndb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6utndb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-left-sharp-fill" {...props}></Icon>
