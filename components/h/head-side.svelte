<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6gzs_b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6gzs_b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:head-side" {...props}></Icon>
