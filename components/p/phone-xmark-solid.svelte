<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2qvr34yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s2qvr34yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:phone-xmark-solid" {...props}></Icon>
