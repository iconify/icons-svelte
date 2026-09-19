<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8wst0exq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z8wst0exq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:codecov" {...props}></Icon>
