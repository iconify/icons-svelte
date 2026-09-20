<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h61c-tcnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h61c-tcnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:expand" {...props}></Icon>
