<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxt7gwb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxt7gwb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:mail-option" {...props}></Icon>
