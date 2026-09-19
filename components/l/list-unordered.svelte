<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cipwxkccr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cipwxkccr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:list-unordered" {...props}></Icon>
