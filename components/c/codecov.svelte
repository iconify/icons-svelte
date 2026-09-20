<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9joz9bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9joz9bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:codecov" {...props}></Icon>
