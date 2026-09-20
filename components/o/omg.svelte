<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ian6zrbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ian6zrbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:omg" {...props}></Icon>
