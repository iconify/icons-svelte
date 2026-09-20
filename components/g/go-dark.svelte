<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx5d-bc1s.css';
import '../../css/h/hvfmwi7nn.css';
import '../../css/g/gmsdegu5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":207,"height":78};
const content = `<g class="nx5d-bc1s"><path class="hvfmwi7nn"/><path class="gmsdegu5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:go-dark" {...props}></Icon>
