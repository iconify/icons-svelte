<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9q6e3ozi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9q6e3ozi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:label-fill-round" {...props}></Icon>
