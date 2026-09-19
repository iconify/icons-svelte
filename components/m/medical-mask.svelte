<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x19w_acyj.css';
import '../../css/v/vpd7rkvil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x19w_acyj"/><path class="vpd7rkvil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:medical-mask" {...props}></Icon>
