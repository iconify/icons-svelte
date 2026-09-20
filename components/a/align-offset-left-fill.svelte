<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpali2b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpali2b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-offset-left-fill" {...props}></Icon>
