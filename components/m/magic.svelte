<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e31tmz-oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e31tmz-oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:magic" {...props}></Icon>
