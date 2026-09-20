<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joeavmn4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="joeavmn4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-minimise-outline" {...props}></Icon>
