<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1rc0yboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1rc0yboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:graduation-cap-1" {...props}></Icon>
