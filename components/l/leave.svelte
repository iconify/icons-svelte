<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v747uwb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v747uwb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:leave" {...props}></Icon>
