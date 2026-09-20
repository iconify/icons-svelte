<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g50cx0bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g50cx0bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:folder-upload" {...props}></Icon>
