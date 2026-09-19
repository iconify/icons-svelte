<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0h7pmb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0h7pmb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:creative-commons" {...props}></Icon>
