<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2q3-ubup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2q3-ubup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:package-question" {...props}></Icon>
