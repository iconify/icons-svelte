<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyeh7w0zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jyeh7w0zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:close-circle-fill" {...props}></Icon>
