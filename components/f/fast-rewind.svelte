<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbgfdabov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbgfdabov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:fast-rewind" {...props}></Icon>
