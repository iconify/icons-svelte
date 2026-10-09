<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id1bkk3ua.css';
import '../../css/g/g4zjvqbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="id1bkk3ua"/><path class="g4zjvqbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fishing-48" {...props}></Icon>
