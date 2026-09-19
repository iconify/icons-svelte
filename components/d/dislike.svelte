<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8od00b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8od00b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:dislike" {...props}></Icon>
