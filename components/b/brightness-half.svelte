<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqoppnb6n.css';
import '../../css/c/cv9731b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqoppnb6n"/><path class="cv9731b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:brightness-half" {...props}></Icon>
