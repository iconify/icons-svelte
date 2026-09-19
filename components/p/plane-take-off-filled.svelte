<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3p65ddzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3p65ddzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:plane-take-off-filled" {...props}></Icon>
