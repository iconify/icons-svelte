<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxgf4qeum.css';
import '../../css/c/c_ewb9bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxgf4qeum"/><path class="c_ewb9bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mts" {...props}></Icon>
