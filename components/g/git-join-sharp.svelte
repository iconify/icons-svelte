<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg447v4ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg447v4ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-join-sharp" {...props}></Icon>
