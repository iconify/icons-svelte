<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb74u2v9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb74u2v9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:moonscript" {...props}></Icon>
