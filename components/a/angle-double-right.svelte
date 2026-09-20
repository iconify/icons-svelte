<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev5fk9umj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev5fk9umj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:angle-double-right" {...props}></Icon>
