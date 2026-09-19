<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfi6hnbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfi6hnbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:info-square" {...props}></Icon>
