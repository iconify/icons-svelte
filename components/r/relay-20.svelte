<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhixubcci.css';
import '../../css/b/b98id3jfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nhixubcci"/><path class="b98id3jfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:relay-20" {...props}></Icon>
