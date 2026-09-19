<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jctdg3jzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jctdg3jzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:croissants-pupil" {...props}></Icon>
