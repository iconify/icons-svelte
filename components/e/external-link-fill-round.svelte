<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsdozl7jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsdozl7jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:external-link-fill-round" {...props}></Icon>
