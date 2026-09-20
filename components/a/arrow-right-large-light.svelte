<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epmjb9o9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epmjb9o9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-right-large-light" {...props}></Icon>
