<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jly_eg06t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="jly_eg06t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-devil" {...props}></Icon>
