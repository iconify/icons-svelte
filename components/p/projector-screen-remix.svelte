<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk5-r5guu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sk5-r5guu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:projector-screen-remix" {...props}></Icon>
