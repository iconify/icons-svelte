<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs0on26ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs0on26ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-down-filled" {...props}></Icon>
