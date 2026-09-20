<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egtzl_b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egtzl_b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fastlane" {...props}></Icon>
