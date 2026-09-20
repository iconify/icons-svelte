<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvjt4o66g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-4};
const content = `<path class="nvjt4o66g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:brightness-down" {...props}></Icon>
