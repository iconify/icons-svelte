<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glkmfrbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="glkmfrbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:carambola" {...props}></Icon>
