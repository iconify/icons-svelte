<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5fn18bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5fn18bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:perc" {...props}></Icon>
