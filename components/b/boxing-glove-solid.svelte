<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn1w2eb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn1w2eb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:boxing-glove-solid" {...props}></Icon>
