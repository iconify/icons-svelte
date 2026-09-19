<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs1nb0bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qs1nb0bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:board" {...props}></Icon>
