<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_vzkekvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_vzkekvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:caret-circle-up" {...props}></Icon>
