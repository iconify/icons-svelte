<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvfhn7b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":999,"height":1000};
const content = `<path class="fvfhn7b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-unhappy" {...props}></Icon>
