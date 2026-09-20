<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh0f9ob6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kh0f9ob6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hotel-fill" {...props}></Icon>
