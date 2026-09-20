<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlxfrac8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":220,"height":220};
const content = `<path clip-rule="evenodd" class="qlxfrac8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pinecone" {...props}></Icon>
