<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myiznqbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="myiznqbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:file-word" {...props}></Icon>
