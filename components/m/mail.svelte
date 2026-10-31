<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/w/weo9vnbgh.css';
import '../../css/b/b0vrlib6h.css';
import '../../css/c/cd1yi91ez.css';
import '../../css/f/f88gcobup.css';
import '../../css/h/hbfe0bbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="weo9vnbgh wm-shadow"/><path class="b0vrlib6h wm-shadow"/><path class="cd1yi91ez"/><path class="f88gcobup"/><path class="hbfe0bbyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:mail" {...props}></Icon>
