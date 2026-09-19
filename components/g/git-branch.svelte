<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnqsujb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnqsujb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:git-branch" {...props}></Icon>
