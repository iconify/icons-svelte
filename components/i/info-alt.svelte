<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfle56dsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfle56dsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:info-alt" {...props}></Icon>
