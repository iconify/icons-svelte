<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9h87yb9c.css';
import '../../css/j/jkn1k3bqn.css';
import '../../css/d/d6ao8lora.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="s9h87yb9c"><path clip-rule="evenodd" class="jkn1k3bqn"/><path class="d6ao8lora"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:map-marker" {...props}></Icon>
