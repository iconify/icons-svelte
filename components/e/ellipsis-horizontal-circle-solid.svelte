<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivco7bn6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ivco7bn6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ellipsis-horizontal-circle-solid" {...props}></Icon>
