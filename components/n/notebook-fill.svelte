<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xae85ttds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xae85ttds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:notebook-fill" {...props}></Icon>
