<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-_kdbbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-_kdbbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cutter-solid" {...props}></Icon>
