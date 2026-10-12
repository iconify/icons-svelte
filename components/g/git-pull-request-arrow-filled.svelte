<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ano5szbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ano5szbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-pull-request-arrow-filled" {...props}></Icon>
