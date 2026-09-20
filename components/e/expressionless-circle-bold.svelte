<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w311_ebvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w311_ebvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:expressionless-circle-bold" {...props}></Icon>
