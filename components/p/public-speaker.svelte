<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byx7xvb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="byx7xvb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:public-speaker" {...props}></Icon>
