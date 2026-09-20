<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa-2nubue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa-2nubue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bottle" {...props}></Icon>
