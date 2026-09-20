<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h52a2qe1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h52a2qe1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:film-sharp-fill" {...props}></Icon>
