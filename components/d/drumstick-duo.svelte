<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v99-kxb3s.css';
import '../../css/j/j0jt8n8se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary v99-kxb3s"/><path class="j0jt8n8se primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:drumstick-duo" {...props}></Icon>
