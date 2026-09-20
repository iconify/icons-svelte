<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euxjhwbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="euxjhwbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-square-up" {...props}></Icon>
