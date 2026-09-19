<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2w0dmuau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2w0dmuau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cube-alt-02-filled" {...props}></Icon>
