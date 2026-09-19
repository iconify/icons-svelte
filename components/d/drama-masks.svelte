<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfb5v-moa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dfb5v-moa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:drama-masks" {...props}></Icon>
