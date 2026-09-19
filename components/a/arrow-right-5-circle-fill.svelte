<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bovqn3gyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bovqn3gyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-5-circle-fill" {...props}></Icon>
