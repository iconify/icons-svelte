<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3ma8esqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3ma8esqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:git-commit-vertical" {...props}></Icon>
