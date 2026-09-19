<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw8fk__of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw8fk__of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:apple-iphone" {...props}></Icon>
