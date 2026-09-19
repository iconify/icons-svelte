<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw14af3mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iw14af3mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:flip-horizontal" {...props}></Icon>
