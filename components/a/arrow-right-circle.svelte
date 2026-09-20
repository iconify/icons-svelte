<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwvk9yb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwvk9yb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:arrow-right-circle" {...props}></Icon>
