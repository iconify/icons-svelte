<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asso8q0pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="asso8q0pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-4-square-fill" {...props}></Icon>
