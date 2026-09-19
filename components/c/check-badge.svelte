<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twd58db8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="twd58db8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:check-badge" {...props}></Icon>
