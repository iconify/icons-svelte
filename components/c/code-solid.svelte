<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wigyevgyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wigyevgyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:code-solid" {...props}></Icon>
