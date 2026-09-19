<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgpkd5u5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgpkd5u5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-bar-down-filled" {...props}></Icon>
