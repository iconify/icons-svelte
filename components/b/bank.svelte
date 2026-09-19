<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn6xy5bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kn6xy5bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bank" {...props}></Icon>
