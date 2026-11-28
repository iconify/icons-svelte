<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoqkcl5ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qoqkcl5ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:notebook-check" {...props}></Icon>
