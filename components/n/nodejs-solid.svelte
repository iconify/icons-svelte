<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlk9qlb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="mlk9qlb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:nodejs-solid" {...props}></Icon>
