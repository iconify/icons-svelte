<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y26g7bcbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y26g7bcbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:restart" {...props}></Icon>
