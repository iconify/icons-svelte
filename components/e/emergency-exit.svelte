<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls6a6jbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls6a6jbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:emergency-exit" {...props}></Icon>
