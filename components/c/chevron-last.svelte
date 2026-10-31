<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/k/kioy7272c.css';
import '../../css/q/qg3owvukv.css';
import '../../css/o/ooj8cp7ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="kioy7272c wm-shadow"/><path class="qg3owvukv wm-shadow"/><path class="ooj8cp7ju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:chevron-last" {...props}></Icon>
