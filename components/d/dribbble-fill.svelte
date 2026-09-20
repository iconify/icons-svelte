<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doeqvm1kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doeqvm1kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dribbble-fill" {...props}></Icon>
