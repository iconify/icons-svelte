<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/temj2-uou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="temj2-uou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:git-branch-check" {...props}></Icon>
