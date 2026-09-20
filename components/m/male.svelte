<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dogu1ji5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2.5};
const content = `<path class="dogu1ji5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:male" {...props}></Icon>
