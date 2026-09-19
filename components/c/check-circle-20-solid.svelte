<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq7us0bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wq7us0bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:check-circle-20-solid" {...props}></Icon>
