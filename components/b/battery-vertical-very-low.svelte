<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vek-gjbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vek-gjbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:battery-vertical-very-low" {...props}></Icon>
