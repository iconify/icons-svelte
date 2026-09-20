<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_vy8db8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o_vy8db8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:incognito-mode-fill" {...props}></Icon>
