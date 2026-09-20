<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onn7nldop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="onn7nldop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:reply-filled" {...props}></Icon>
