<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk6_l5bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk6_l5bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:checkbox-minus" {...props}></Icon>
