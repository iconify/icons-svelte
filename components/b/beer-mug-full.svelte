<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfzc_4bcf.css';
import '../../css/x/x645877qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfzc_4bcf"/><path class="x645877qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:beer-mug-full" {...props}></Icon>
