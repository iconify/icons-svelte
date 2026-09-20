<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypqjqacjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypqjqacjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:credit-card-minus-solid" {...props}></Icon>
