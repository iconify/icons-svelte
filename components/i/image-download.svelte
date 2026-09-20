<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qtn6etb4o.css';
import '../../css/h/ho3oitlqc.css';
import '../../css/u/uqu3qqpqj.css';
import '../../css/k/k0i139bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qtn6etb4o"/><path class="ho3oitlqc"/><path class="uqu3qqpqj"/><path class="k0i139bgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:image-download" {...props}></Icon>
