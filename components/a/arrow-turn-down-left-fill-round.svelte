<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzcsvybug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzcsvybug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-down-left-fill-round" {...props}></Icon>
