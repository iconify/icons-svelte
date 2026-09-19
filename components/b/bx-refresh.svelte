<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxayh14fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxayh14fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-refresh" {...props}></Icon>
