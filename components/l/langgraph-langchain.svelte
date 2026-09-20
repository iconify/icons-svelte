<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b79l61bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b79l61bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:langgraph-langchain" {...props}></Icon>
