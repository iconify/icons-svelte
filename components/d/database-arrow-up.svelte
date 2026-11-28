<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v52curbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v52curbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:database-arrow-up" {...props}></Icon>
