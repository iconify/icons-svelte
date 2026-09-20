<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygo2ytbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ygo2ytbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chart-alt-fill" {...props}></Icon>
