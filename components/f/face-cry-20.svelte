<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw3xaacjo.css';
import '../../css/b/bc6ktqbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="bc6ktqbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:face-cry-20" {...props}></Icon>
