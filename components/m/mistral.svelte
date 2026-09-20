<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmxqd5bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmxqd5bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:mistral" {...props}></Icon>
