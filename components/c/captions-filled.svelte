<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvf9oixuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvf9oixuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:captions-filled" {...props}></Icon>
