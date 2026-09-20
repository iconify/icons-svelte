<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w70lsgs8c.css';
import '../../css/d/dlpk8tb7x.css';
import '../../css/p/pvytqg7gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="w70lsgs8c"><path class="dlpk8tb7x"/><path class="pvytqg7gd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:paragraphs-symbol" {...props}></Icon>
