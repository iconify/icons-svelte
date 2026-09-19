<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjf9ohdok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wjf9ohdok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ancient-columns" {...props}></Icon>
