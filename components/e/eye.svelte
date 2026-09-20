<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/sc0c9hqgy.css';
import '../../css/t/tkn-bnbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="sc0c9hqgy"/><path class="tkn-bnbos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:eye" {...props}></Icon>
