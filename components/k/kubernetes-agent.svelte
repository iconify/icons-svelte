<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcueb5bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fcueb5bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:kubernetes-agent" {...props}></Icon>
