<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1v6c2b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1v6c2b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:bicep" {...props}></Icon>
