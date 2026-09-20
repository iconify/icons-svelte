<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajvn4_1qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajvn4_1qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:align-vertical-bottom" {...props}></Icon>
