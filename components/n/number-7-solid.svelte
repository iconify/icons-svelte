<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_7jbxxkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_7jbxxkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-7-solid" {...props}></Icon>
