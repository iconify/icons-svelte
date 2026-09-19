<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dsbl1nj-w.css';
import '../../css/x/xcetmgeuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#svgIDa)"><path clip-rule="evenodd" class="dsbl1nj-w"/></g><defs><clipPath id="svgIDa"><path class="xcetmgeuw"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-left-circle" {...props}></Icon>
