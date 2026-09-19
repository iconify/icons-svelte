<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-q1p9pqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-q1p9pqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:code-branch-outline" {...props}></Icon>
