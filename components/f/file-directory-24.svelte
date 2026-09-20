<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5y_62azb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5y_62azb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-directory-24" {...props}></Icon>
