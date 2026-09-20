<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tax5f0byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tax5f0byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bond" {...props}></Icon>
