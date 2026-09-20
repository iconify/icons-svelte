<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke-883_3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke-883_3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-gitlab" {...props}></Icon>
