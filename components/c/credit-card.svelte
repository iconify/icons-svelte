<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihiwsjbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihiwsjbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:credit-card" {...props}></Icon>
