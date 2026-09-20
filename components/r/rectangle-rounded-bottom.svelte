<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rifrj-b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rifrj-b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rectangle-rounded-bottom" {...props}></Icon>
