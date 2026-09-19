<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaxyklglx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yaxyklglx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:link-alt-01" {...props}></Icon>
