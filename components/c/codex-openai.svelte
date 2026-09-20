<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shnqohozs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shnqohozs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:codex-openai" {...props}></Icon>
