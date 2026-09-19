<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvu0d3bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvu0d3bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-show-8-gen-2" {...props}></Icon>
