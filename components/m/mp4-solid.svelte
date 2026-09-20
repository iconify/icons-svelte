<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnuh6xh8p.css';
import '../../css/f/fqore9c7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vnuh6xh8p"/><path clip-rule="evenodd" class="fqore9c7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mp4-solid" {...props}></Icon>
