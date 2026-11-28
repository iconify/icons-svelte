<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6u-kgb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6u-kgb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:home-plus" {...props}></Icon>
