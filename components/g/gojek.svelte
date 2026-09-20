<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ken-7tb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ken-7tb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gojek" {...props}></Icon>
