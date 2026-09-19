<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhh-_dwpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhh-_dwpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:close-circle-fill" {...props}></Icon>
