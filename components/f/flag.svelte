<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc-i_7bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc-i_7bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:flag" {...props}></Icon>
