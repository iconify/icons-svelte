<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y45y97bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y45y97bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-merge-round" {...props}></Icon>
