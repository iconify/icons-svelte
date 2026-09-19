<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr7n_jb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr7n_jb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:binocular" {...props}></Icon>
