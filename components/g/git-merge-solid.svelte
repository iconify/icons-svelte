<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyup4eb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyup4eb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:git-merge-solid" {...props}></Icon>
