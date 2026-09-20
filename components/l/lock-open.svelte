<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvif2zbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvif2zbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:lock-open" {...props}></Icon>
