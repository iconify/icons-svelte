<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb-md8jcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-md8jcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:gift" {...props}></Icon>
