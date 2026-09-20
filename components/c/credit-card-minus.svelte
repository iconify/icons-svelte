<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccgk95bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccgk95bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:credit-card-minus" {...props}></Icon>
