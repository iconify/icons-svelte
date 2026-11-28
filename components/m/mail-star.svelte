<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwpuxgb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwpuxgb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mail-star" {...props}></Icon>
