<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw9659bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw9659bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:plane-arrow-up" {...props}></Icon>
