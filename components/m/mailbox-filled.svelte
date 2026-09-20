<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jwsgkxbib.css';
import '../../css/n/nalw8vbji.css';
import '../../css/j/jnrwwtxlf.css';
import '../../css/t/tqza-jbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jwsgkxbib"/><path clip-rule="evenodd" class="nalw8vbji"/><path class="jnrwwtxlf"/><path clip-rule="evenodd" class="tqza-jbmx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mailbox-filled" {...props}></Icon>
