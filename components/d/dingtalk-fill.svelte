<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weim-6bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="weim-6bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dingtalk-fill" {...props}></Icon>
