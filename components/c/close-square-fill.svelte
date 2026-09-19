<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh7b9tr9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh7b9tr9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:close-square-fill" {...props}></Icon>
