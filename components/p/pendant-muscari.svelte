<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afn6kfbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afn6kfbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pendant-muscari" {...props}></Icon>
