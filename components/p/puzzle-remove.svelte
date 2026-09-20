<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a56q-fomj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a56q-fomj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:puzzle-remove" {...props}></Icon>
