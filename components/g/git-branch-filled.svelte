<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqmplqd4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqmplqd4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-branch-filled" {...props}></Icon>
