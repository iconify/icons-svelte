<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-ba65uzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-ba65uzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:align-left-solid" {...props}></Icon>
