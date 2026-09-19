<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs2dvebnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bs2dvebnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:align-text-justify-right" {...props}></Icon>
