<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa0rcoq6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa0rcoq6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cpu-fill-round" {...props}></Icon>
