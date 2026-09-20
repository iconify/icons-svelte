<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqr06mblf.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cvba9qpke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<defs><path id="SVGr9eWYbHE" class="iqr06mblf"/></defs><mask id="SVGvH4ZXd9x" class="cuyn6tgcc"><use href="#SVGr9eWYbHE"/></mask><g class="cuyn6tgcc"><use href="#SVGr9eWYbHE"/><path mask="url(#SVGvH4ZXd9x)" class="cvba9qpke"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:panel-left-minimized" {...props}></Icon>
