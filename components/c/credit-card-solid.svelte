<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/errg8-z4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="errg8-z4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:credit-card-solid" {...props}></Icon>
