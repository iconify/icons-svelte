<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhb3vsb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhb3vsb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:graph-ql" {...props}></Icon>
