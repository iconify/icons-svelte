<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqmrd89er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqmrd89er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:get" {...props}></Icon>
