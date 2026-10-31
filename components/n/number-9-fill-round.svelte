<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op1oeqo0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op1oeqo0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-9-fill-round" {...props}></Icon>
