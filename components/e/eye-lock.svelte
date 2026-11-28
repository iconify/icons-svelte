<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5f2ztzfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5f2ztzfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:eye-lock" {...props}></Icon>
